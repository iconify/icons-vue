<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byr1kccnj.css';
import '../../css/v/v5yc14bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="byr1kccnj"/><path class="v5yc14bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:inbox-48" /></template>
