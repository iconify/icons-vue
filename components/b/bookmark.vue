<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imvqoebdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="imvqoebdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:bookmark" /></template>
