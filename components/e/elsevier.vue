<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo05-abpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo05-abpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:elsevier" /></template>
