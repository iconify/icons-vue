<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1upd6b8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j1upd6b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache-tika-dark" /></template>
