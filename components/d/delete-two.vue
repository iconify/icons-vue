<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt1r6l-8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lt1r6l-8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:delete-two" /></template>
