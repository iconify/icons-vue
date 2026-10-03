<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0e4ebeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0e4ebeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:co2" /></template>
