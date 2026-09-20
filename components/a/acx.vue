<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udn5eiblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udn5eiblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:acx" /></template>
