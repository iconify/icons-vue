<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izgbh1b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="izgbh1b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-lizard" /></template>
