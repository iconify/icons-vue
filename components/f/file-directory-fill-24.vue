<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waxglib2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waxglib2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-fill-24" /></template>
