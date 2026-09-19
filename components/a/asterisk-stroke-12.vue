<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_1zd_p4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u_1zd_p4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:asterisk-stroke-12" /></template>
