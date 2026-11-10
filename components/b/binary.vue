<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5n-bx3th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5n-bx3th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:binary" /></template>
