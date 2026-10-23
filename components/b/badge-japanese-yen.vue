<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmlnfs7bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmlnfs7bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-japanese-yen" /></template>
