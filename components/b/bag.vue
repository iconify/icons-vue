<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp8doyjes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8doyjes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bag" /></template>
