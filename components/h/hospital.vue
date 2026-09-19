<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn8ep4exf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rn8ep4exf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hospital" /></template>
