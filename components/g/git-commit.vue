<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2ijtijuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2ijtijuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-commit" /></template>
