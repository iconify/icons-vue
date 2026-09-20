<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orp70za5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orp70za5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gmpd" /></template>
