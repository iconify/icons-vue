<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb201_2ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fb201_2ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ipcs" /></template>
