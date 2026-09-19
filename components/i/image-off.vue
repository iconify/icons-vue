<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcsk-jbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rcsk-jbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-off" /></template>
