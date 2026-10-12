<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezuoaobcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezuoaobcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:chevron-end-double" /></template>
