<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2r_egrqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2r_egrqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bluetooth-b" /></template>
