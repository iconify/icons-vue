<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbp_cdbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbp_cdbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chef-hat" /></template>
