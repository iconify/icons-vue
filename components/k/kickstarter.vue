<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwkxq6bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jwkxq6bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:kickstarter" /></template>
