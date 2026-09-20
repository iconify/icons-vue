<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixcjz-wtv.css';
import '../../css/u/uhf9ggjia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixcjz-wtv"/><path class="uhf9ggjia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:fruit-apricot-bold" /></template>
