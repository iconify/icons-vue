<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itk3lzbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":735};
const content = `<path class="itk3lzbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:b-upper-case" /></template>
