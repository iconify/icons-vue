<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p06nvcb0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p06nvcb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asrock-light" /></template>
