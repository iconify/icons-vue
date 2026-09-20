<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvzhtd08i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zvzhtd08i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:duck" /></template>
