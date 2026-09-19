<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elcz3zykd.css';
import '../../css/q/q_tt9nb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer elcz3zykd"/><path class="duoicon-primary-layer q_tt9nb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:coin-stack" /></template>
