<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo01anvpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zo01anvpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-up-right-box" /></template>
