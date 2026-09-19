<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdzhxmbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdzhxmbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:devices" /></template>
