<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i77-37njs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i77-37njs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-triangle" /></template>
