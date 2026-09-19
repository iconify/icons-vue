<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9h4qu6lx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u9h4qu6lx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-f" /></template>
