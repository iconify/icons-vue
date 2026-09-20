<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_1x7ub7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a_1x7ub7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:discord-fill-16" /></template>
