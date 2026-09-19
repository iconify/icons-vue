<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic049nbdu.css';
import '../../css/u/ulq1acb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ic049nbdu"/><path class="ulq1acb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:business" /></template>
