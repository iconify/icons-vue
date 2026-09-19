<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tho4hgacv.css';
import '../../css/l/lj8aahbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tho4hgacv"/><path class="lj8aahbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:home-smile" /></template>
