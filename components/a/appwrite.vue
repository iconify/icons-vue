<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acdtw7b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="acdtw7b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:appwrite" /></template>
