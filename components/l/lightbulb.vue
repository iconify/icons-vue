<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k90sxq3fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="k90sxq3fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lightbulb" /></template>
