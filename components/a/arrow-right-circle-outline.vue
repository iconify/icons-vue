<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwh-h-rhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jwh-h-rhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-right-circle-outline" /></template>
