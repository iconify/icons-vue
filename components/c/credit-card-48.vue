<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txant-bxm.css';
import '../../css/m/mc_31q86u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="txant-bxm"/><path class="mc_31q86u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-48" /></template>
