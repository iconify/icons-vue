<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h93190bvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="h93190bvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:futbol" /></template>
