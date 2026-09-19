<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg_6pjuzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rg_6pjuzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-forward" /></template>
