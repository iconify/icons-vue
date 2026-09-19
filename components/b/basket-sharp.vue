<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkm6zyj7x.css';
import '../../css/i/idjmobcht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jkm6zyj7x"/><path class="idjmobcht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:basket-sharp" /></template>
