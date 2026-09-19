<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7_a9xxqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7_a9xxqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:code-pull-request-arrow-left" /></template>
