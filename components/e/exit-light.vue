<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zavdn0vkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zavdn0vkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:exit-light" /></template>
