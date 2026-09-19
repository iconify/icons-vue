<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baqr00whe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="baqr00whe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:lightbulb" /></template>
