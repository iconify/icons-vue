<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy6uiklgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dy6uiklgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:denied-outline" /></template>
