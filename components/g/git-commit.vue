<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs3gkc0he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bs3gkc0he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:git-commit" /></template>
