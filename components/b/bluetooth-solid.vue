<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jws9cpgqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jws9cpgqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bluetooth-solid" /></template>
