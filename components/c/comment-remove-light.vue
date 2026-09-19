<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prhzfybbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prhzfybbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-remove-light" /></template>
