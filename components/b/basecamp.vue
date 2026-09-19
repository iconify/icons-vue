<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qo99cgbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="qo99cgbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:basecamp" /></template>
