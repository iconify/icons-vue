<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-scgcc9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v-scgcc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:list-outdent" /></template>
