<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rta1vqbep.css';
import '../../css/e/eldc1fran.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rta1vqbep"/><path class="eldc1fran"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bel" /></template>
