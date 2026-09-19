<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh810pbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="eh810pbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dice-six" /></template>
