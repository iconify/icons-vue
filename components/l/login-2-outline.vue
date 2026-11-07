<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olusrszwm.css';
import '../../css/j/j-an33b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olusrszwm"/><path class="j-an33b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-2-outline" /></template>
