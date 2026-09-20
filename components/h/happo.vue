<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt4mkab9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kt4mkab9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:happo" /></template>
