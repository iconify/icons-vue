<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uftgi16-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="uftgi16-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:book-circle-fill" /></template>
