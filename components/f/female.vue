<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f--u3xscy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="f--u3xscy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:female" /></template>
