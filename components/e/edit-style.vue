<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3tddc7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ek3tddc7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:edit-style" /></template>
