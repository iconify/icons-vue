<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wopchbcny.css';
import '../../css/w/wjqe3kpku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wopchbcny"/><path class="wjqe3kpku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:git-commit-20-bold" /></template>
