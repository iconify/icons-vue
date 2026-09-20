<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mld5sg2zl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mld5sg2zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gate-alert" /></template>
