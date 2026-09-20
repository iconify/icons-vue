<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcu5bso8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcu5bso8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ego" /></template>
