<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk373-b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wk373-b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle-and-euro" /></template>
