<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjelpi7gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bjelpi7gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:black-medium-square" /></template>
