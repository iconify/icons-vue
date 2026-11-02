<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe3uj_7em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe3uj_7em"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:library-fill" /></template>
