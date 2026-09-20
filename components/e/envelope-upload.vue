<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp2_cybfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp2_cybfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope-upload" /></template>
