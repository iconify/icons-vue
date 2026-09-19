<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6g1_dr5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="j6g1_dr5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-middle-top" /></template>
