<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqajkfaqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqajkfaqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leak-48-bold" /></template>
