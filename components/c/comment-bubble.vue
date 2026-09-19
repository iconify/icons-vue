<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqj8fxb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1600};
const content = `<path class="nqj8fxb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:comment-bubble" /></template>
