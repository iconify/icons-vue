<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t26f_urlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t26f_urlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-up-from-wide-rectangle-outline" /></template>
