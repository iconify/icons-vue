<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpmmk1r3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpmmk1r3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:info" /></template>
