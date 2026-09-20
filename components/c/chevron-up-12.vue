<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbjau4brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="kbjau4brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:chevron-up-12" /></template>
