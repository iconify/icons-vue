<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidcoy8qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qidcoy8qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-to-wide-rectangle-outline" /></template>
