<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6cipq81a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6cipq81a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:inbox-fill" /></template>
