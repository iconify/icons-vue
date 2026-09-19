<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfqxogb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="hfqxogb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-mastercard" /></template>
