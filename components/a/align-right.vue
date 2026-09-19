<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwtu_ug1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwtu_ug1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:align-right" /></template>
