<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-qif2x6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-qif2x6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-off" /></template>
