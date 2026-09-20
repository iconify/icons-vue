<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd5jlqbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bd5jlqbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:gitea" /></template>
