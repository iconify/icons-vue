<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iavwc_xnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iavwc_xnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-close-fill" /></template>
