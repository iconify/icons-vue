<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzlo_6bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzlo_6bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:key-skeleton-alt" /></template>
