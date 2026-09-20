<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff_6cdc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff_6cdc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-right-b" /></template>
