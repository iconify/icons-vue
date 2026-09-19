<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aog-1ebri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aog-1ebri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-five-small" /></template>
