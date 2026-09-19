<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic3wg7_sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="ic3wg7_sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cloudaltupload" /></template>
