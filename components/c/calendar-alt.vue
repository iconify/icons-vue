<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh0-akcec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="eh0-akcec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:calendar-alt" /></template>
