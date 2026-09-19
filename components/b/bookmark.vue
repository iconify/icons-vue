<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brh31tegt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brh31tegt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bookmark" /></template>
