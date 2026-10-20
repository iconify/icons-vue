<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc2oi_bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc2oi_bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cable" /></template>
