<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytc_j7pdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytc_j7pdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-eye-outline" /></template>
