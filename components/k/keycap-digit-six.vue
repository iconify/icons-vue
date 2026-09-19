<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0c92zbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d0c92zbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-six" /></template>
