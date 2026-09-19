<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgd5uubak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sgd5uubak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-zipper" /></template>
