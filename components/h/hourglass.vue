<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e29a1ibtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e29a1ibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:hourglass" /></template>
