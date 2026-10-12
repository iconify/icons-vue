<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdylnj5ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pdylnj5ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-up-20" /></template>
