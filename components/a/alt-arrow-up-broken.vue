<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzafjjlaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzafjjlaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-broken" /></template>
