<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p97jexevo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p97jexevo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:facebook-fill-16" /></template>
