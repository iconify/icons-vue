<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epjfojbru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="epjfojbru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:directus-light" /></template>
