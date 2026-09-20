<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gphionylb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gphionylb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-commit-filled" /></template>
