<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4iz5erop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4iz5erop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:add-ring-fill" /></template>
