<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvhjv7b-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tvhjv7b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:checkbox-fill-16" /></template>
