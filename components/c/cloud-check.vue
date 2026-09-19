<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk1b1pbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kk1b1pbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:cloud-check" /></template>
