<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwe1n2brt.css';
import '../../css/g/g_zd9bbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwe1n2brt"/><path class="g_zd9bbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-parking-place-filled" /></template>
