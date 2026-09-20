<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz7exac3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7exac3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:error-circle-filled" /></template>
