<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmy3jvb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmy3jvb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cookie" /></template>
