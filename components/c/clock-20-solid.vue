<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzxmglb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="uzxmglb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clock-20-solid" /></template>
