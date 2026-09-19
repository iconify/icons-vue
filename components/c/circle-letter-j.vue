<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al6qvnkly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="al6qvnkly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-j" /></template>
