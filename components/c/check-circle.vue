<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpn46pbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpn46pbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:check-circle" /></template>
