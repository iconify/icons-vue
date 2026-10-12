<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xemez9bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xemez9bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-start-line" /></template>
