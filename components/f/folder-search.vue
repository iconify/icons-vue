<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn2kn79sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rn2kn79sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-search" /></template>
