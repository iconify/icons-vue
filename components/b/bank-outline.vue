<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miukfq3du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="miukfq3du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bank-outline" /></template>
