<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7g0cmbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7g0cmbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-coinbase" /></template>
