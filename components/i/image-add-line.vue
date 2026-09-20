<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kko3h3bui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kko3h3bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-add-line" /></template>
