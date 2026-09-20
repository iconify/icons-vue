<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mih9617if.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mih9617if"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-t" /></template>
