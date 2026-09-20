<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd25jv_3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd25jv_3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dozzle" /></template>
