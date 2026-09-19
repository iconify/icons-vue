<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwdj50gvt.css';
import '../../css/c/ch6_fcbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwdj50gvt"/><path class="ch6_fcbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:location-plus" /></template>
