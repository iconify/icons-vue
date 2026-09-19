<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfw9hvbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="yfw9hvbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hibernate" /></template>
