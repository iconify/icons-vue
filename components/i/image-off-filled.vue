<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu95p048q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zu95p048q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:image-off-filled" /></template>
