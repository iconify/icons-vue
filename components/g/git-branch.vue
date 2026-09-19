<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i045xv0ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i045xv0ds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:git-branch" /></template>
