<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tamqo7ynr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tamqo7ynr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-variant" /></template>
