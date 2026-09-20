<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3kv63imc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3kv63imc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:library-24" /></template>
