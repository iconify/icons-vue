<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk-cdeb0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yk-cdeb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-javascript" /></template>
