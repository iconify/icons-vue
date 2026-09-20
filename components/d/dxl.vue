<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbs-x1etz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbs-x1etz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dxl" /></template>
