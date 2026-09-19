<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3lmh7etc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="k3lmh7etc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:file-question" /></template>
