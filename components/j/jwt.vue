<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc3yz6byc.css';
import '../../css/z/zdd0vz74c.css';
import '../../css/h/hz-xq7bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc3yz6byc"/><path class="zdd0vz74c"/><path class="hz-xq7bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:jwt" /></template>
