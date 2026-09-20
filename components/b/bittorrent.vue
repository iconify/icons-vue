<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxka6984l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxka6984l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bittorrent" /></template>
