<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufv5pizdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufv5pizdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-turn-up-left" /></template>
