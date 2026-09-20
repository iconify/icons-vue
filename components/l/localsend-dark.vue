<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c15i9ac9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c15i9ac9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:localsend-dark" /></template>
