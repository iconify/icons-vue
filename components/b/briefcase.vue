<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj4rddc0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bj4rddc0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:briefcase" /></template>
