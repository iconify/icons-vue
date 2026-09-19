<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t88t3ip3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t88t3ip3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-arrow-down" /></template>
