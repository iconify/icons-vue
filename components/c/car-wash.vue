<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa8p-hbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa8p-hbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:car-wash" /></template>
