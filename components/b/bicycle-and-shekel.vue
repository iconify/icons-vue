<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqb-96wwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eqb-96wwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-shekel" /></template>
