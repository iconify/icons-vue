<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxcczh6dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxcczh6dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-3-square" /></template>
