<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpz4-dbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rpz4-dbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:broom" /></template>
