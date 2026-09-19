<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au_w-gbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="au_w-gbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:arrange-bring-forward" /></template>
