<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhytieb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhytieb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-distribute-center" /></template>
