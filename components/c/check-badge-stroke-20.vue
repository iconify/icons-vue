<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqbane7zo.css';
import '../../css/v/vuoehu_3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kqbane7zo"/><path class="vuoehu_3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-badge-stroke-20" /></template>
