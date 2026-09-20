<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd0h3wb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd0h3wb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-linear" /></template>
