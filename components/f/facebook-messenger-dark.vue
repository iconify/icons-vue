<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-4u1lb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-4u1lb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:facebook-messenger-dark" /></template>
