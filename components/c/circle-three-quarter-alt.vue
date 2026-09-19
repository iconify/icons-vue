<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xt6wxsl1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt6wxsl1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-three-quarter-alt" /></template>
