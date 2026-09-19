<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpjp_6bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kpjp_6bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:credit-card-fill-12" /></template>
