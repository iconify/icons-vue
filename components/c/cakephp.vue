<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwt1mrh8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="uwt1mrh8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:cakephp" /></template>
