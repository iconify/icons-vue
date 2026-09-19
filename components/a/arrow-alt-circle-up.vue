<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj-g3nbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wj-g3nbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:arrow-alt-circle-up" /></template>
