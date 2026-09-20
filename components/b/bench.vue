<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr8xndb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qr8xndb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bench" /></template>
