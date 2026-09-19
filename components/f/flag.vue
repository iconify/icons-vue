<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi-iagg1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oi-iagg1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:flag" /></template>
