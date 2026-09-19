<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo_sdj8_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":1024};
const content = `<path class="fo_sdj8_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:i-upper-case" /></template>
