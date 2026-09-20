<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vswfw9aqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vswfw9aqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:briefcase-outline" /></template>
