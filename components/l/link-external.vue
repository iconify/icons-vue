<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyd8mfyoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyd8mfyoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:link-external" /></template>
