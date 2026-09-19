<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3s4zvj1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":663};
const content = `<path class="v3s4zvj1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:heart" /></template>
