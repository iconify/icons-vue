<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btc7y3bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btc7y3bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ark-ecosystem" /></template>
