<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1ud49bhs.css';
import '../../css/z/zhvsnqbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ud49bhs"/><path class="zhvsnqbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:key-skeleton-alt" /></template>
