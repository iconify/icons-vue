<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4lzhxbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="a4lzhxbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark" /></template>
