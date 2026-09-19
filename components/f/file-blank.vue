<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofcnx_x9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofcnx_x9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:file-blank" /></template>
