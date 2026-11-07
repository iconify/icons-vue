<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmlcj5izr.css';
import '../../css/q/qkmo0ac8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmlcj5izr"/><path clip-rule="evenodd" class="qkmo0ac8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-open-bold" /></template>
