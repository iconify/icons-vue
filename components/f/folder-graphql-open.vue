<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yypzf8b8r.css';
import '../../css/s/s1altqbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yypzf8b8r"/><path class="s1altqbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-graphql-open" /></template>
