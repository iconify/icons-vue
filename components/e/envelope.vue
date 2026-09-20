<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afdq6s1fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afdq6s1fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:envelope" /></template>
