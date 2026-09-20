<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z90tcxiee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="z90tcxiee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:edit-alt-5" /></template>
