<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg7s-p90e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7s-p90e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:chevron-up-double" /></template>
