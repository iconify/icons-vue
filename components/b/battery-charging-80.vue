<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaff0bcie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaff0bcie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-charging-80" /></template>
