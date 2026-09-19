<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdn5_zp5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdn5_zp5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:language-english" /></template>
