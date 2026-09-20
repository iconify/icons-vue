<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnt2txbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnt2txbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:close-circle-filled" /></template>
