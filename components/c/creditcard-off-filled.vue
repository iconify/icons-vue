<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5_gckbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5_gckbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:creditcard-off-filled" /></template>
