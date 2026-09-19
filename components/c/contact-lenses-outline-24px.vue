<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_i-_ub5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_i-_ub5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contact-lenses-outline-24px" /></template>
