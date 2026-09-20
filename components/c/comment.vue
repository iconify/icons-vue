<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-rfybpgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-rfybpgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:comment" /></template>
