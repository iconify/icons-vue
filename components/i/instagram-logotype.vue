<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvr6yacwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvr6yacwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:instagram-logotype" /></template>
