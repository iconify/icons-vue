<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sec9lqbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sec9lqbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:banknote-dollar" /></template>
