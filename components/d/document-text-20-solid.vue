<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av0c_6b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="av0c_6b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-text-20-solid" /></template>
