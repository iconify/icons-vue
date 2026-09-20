<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-al7jbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-al7jbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:codechef" /></template>
