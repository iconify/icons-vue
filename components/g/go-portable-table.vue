<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-9ylyc-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9ylyc-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:go-portable-table" /></template>
