<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h63z7hbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h63z7hbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:close-small" /></template>
