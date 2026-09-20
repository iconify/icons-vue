<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohujd2_nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohujd2_nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-x-sharp" /></template>
