<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3kj7i7gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p3kj7i7gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:briefcase-with-heavy-six-point-asterisk" /></template>
