<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teozd_bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="teozd_bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hypermind" /></template>
