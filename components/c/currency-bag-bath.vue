<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-txjnb-q.css';
import '../../css/g/g13_2rbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-txjnb-q"/><path class="g13_2rbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:currency-bag-bath" /></template>
