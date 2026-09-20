<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2rhd2bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s2rhd2bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:inscribed-stone" /></template>
