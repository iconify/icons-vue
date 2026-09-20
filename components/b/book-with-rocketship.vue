<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giqwm_2jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="giqwm_2jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-rocketship" /></template>
