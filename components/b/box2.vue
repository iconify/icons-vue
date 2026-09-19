<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr9ai5wvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qr9ai5wvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:box2" /></template>
