<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2c-5ubrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r2c-5ubrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-osi" /></template>
