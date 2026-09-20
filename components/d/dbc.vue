<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcu5i0bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcu5i0bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dbc" /></template>
