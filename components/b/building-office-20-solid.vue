<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb95-1bon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jb95-1bon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-office-20-solid" /></template>
