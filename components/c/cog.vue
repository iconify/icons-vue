<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg_m2acwj.css';
import '../../css/h/h2gb18b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg_m2acwj"/><path class="h2gb18b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cog" /></template>
