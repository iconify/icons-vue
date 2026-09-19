<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sslbt3clz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sslbt3clz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:columns-two-halfs" /></template>
