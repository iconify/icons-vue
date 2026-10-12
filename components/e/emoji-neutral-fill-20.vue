<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9wy74bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h9wy74bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-neutral-fill-20" /></template>
