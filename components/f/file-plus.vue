<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0hz00p_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0hz00p_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-plus" /></template>
