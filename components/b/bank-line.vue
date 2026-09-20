<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxoqcdtnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxoqcdtnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bank-line" /></template>
