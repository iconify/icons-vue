<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzvwx7now.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="uzvwx7now"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:kickstarter-k" /></template>
