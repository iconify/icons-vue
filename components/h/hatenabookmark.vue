<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng0uf7b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":679};
const content = `<path class="ng0uf7b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:hatenabookmark" /></template>
