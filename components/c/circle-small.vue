<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uynuzcb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="uynuzcb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:circle-small" /></template>
