<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quzl_8ckk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzl_8ckk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-multiple-outline" /></template>
