<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce45q_nkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ce45q_nkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-with-cold-sweat" /></template>
