<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft30jne3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ft30jne3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:deletealarm" /></template>
