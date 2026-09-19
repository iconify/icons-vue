<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2wusww1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2wusww1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-check" /></template>
