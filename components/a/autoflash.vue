<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk-6r4b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fk-6r4b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:autoflash" /></template>
