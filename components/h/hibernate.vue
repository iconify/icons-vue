<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f85_jjqda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="f85_jjqda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hibernate" /></template>
