<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-pyqox9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-pyqox9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dev-push-light" /></template>
