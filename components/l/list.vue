<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szew_ymuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="szew_ymuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:list" /></template>
