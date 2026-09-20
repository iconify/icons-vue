<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlo08zxww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlo08zxww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boom-barrier-alert-outline" /></template>
