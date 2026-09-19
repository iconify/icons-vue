<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dovwo7b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dovwo7b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:address-book-small-filled" /></template>
