<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0gfjvbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z0gfjvbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-arrow-up-fill" /></template>
