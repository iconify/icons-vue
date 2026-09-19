<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v10r17syt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="v10r17syt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-jcb" /></template>
