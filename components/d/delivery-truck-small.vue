<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-84ape3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w-84ape3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:delivery-truck-small" /></template>
