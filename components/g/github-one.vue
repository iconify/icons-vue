<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz1je_b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz1je_b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:github-one" /></template>
