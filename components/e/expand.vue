<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka8nnc9vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ka8nnc9vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:expand" /></template>
