<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqhzav2ye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nqhzav2ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folders-outline" /></template>
