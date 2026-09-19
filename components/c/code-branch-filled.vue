<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kio_w0bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kio_w0bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:code-branch-filled" /></template>
