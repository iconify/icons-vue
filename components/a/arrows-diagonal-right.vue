<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7f4-c_ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7f4-c_ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrows-diagonal-right" /></template>
