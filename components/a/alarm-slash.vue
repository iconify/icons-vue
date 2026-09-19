<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqih_6qlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqih_6qlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:alarm-slash" /></template>
