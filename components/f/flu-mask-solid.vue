<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0k8cvblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v0k8cvblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flu-mask-solid" /></template>
