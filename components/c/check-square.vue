<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2oipd3ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e2oipd3ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:check-square" /></template>
