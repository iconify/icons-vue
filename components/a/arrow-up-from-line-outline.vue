<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2f7hu3hn.css';
import '../../css/v/vh0_98nmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2f7hu3hn"/><path class="vh0_98nmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-from-line-outline" /></template>
