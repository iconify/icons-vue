<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1mqx4hvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1mqx4hvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:balloon" /></template>
