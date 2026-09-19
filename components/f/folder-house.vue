<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_5sp8bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c_5sp8bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-house" /></template>
