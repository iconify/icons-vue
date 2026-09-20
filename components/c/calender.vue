<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1p2s7bsm.css';
import '../../css/g/gb7xzgbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1p2s7bsm"/><path class="gb7xzgbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:calender" /></template>
