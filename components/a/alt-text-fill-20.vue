<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyt5vk0em.css';
import '../../css/a/aj1kvdbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nyt5vk0em"/><path class="aj1kvdbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:alt-text-fill-20" /></template>
