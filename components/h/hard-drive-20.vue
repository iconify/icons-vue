<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6-botbkv.css';
import '../../css/i/iih2hu12r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v6-botbkv"/><path class="iih2hu12r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hard-drive-20" /></template>
