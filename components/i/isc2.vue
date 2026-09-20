<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmoy7thqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmoy7thqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:isc2" /></template>
