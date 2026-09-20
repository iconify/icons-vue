<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt0urabjs.css';
import '../../css/m/mgxmn9o8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt0urabjs"/><path class="mgxmn9o8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:filter-duotone" /></template>
