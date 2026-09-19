<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4haehu2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s4haehu2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:happy-face" /></template>
