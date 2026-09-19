<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6f7tdbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d6f7tdbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:face-neutral-dashed" /></template>
