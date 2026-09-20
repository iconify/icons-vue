<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn5532fdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kn5532fdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dislike3-filled" /></template>
