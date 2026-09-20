<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkd14r_yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gkd14r_yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doco-cd-dark" /></template>
