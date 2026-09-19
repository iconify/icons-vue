<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr6xv7y8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rr6xv7y8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:git-fork" /></template>
