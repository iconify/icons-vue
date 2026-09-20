<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jls4p8yza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jls4p8yza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bird-flying" /></template>
