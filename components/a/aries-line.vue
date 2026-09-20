<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq9diw0mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq9diw0mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:aries-line" /></template>
