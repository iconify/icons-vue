<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp1cnh7qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tp1cnh7qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:eye" /></template>
