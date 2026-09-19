<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q83l7ebwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q83l7ebwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:folder-plus" /></template>
