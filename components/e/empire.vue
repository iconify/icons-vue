<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czd8gk1ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="czd8gk1ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:empire" /></template>
