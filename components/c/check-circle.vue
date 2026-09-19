<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3j32acby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="i3j32acby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:check-circle" /></template>
