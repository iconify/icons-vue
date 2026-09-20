<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq7-5m55k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wq7-5m55k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:castle-fill" /></template>
