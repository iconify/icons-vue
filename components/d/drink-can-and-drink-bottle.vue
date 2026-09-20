<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2je18u3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s2je18u3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:drink-can-and-drink-bottle" /></template>
