<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc9ruyn8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jc9ruyn8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:lemon" /></template>
