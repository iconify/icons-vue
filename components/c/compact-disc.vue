<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rprapz00k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="rprapz00k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:compact-disc" /></template>
