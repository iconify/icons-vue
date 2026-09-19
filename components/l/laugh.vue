<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh44u181c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="qh44u181c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:laugh" /></template>
