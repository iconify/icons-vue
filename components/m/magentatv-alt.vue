<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zefbo4jxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zefbo4jxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:magentatv-alt" /></template>
