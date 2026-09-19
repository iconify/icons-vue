<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7oao_qjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7oao_qjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dts-x" /></template>
