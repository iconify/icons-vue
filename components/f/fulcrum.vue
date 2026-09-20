<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arv7yvchw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="arv7yvchw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fulcrum" /></template>
