<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_-9w5b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j_-9w5b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-open-20-solid" /></template>
