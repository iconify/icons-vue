<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbc_5ab7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbc_5ab7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-right-fill" /></template>
