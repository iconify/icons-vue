<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w35knlh6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w35knlh6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bean-off-filled" /></template>
