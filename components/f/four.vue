<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-6sj7bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c-6sj7bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:four" /></template>
