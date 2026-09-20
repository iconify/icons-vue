<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc51d5b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc51d5b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-plus" /></template>
