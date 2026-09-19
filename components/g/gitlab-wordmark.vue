<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbv3kq73b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xbv3kq73b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gitlab-wordmark" /></template>
