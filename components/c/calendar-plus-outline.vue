<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtv447bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jtv447bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-plus-outline" /></template>
