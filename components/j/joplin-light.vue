<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwqzg0boz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwqzg0boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:joplin-light" /></template>
