<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjz6dqb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vjz6dqb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:happy" /></template>
