<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgkjp6s0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgkjp6s0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lock-password-solid" /></template>
