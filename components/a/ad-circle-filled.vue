<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whi__xh_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="whi__xh_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ad-circle-filled" /></template>
