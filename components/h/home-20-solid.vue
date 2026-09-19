<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4-diqj0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w4-diqj0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:home-20-solid" /></template>
