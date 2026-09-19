<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h18a-pf2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="h18a-pf2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:github" /></template>
