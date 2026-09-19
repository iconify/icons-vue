<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la_o4hbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="la_o4hbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:ear-fill" /></template>
