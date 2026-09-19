<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm-3jmkwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":3035,"height":634};
const content = `<path class="fm-3jmkwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:buffalo" /></template>
