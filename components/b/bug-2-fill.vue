<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx2u-p4hj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx2u-p4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bug-2-fill" /></template>
