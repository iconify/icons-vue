<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3ugng94a.css';
import '../../css/j/j4wgwkb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w3ugng94a"/><path class="j4wgwkb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-graphql" /></template>
