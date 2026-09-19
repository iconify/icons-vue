<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_lhe9xti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b_lhe9xti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:droplet" /></template>
