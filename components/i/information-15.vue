<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltx671b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ltx671b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:information-15" /></template>
