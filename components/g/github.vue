<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5jqn4b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z5jqn4b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:github" /></template>
