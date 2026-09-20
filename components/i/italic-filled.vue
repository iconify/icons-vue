<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu-dbm9zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu-dbm9zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:italic-filled" /></template>
