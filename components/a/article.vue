<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6nw9ybaa.css';
import '../../css/n/n3vra2bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6nw9ybaa"/><path class="n3vra2bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:article" /></template>
