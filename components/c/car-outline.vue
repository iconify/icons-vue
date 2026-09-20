<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvf6hzvqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pvf6hzvqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:car-outline" /></template>
