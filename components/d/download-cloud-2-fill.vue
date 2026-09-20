<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axxrmxjip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axxrmxjip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:download-cloud-2-fill" /></template>
