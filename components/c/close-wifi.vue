<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qu7egmbzc.css';
import '../../css/h/hmy4ymk6a.css';
import '../../css/m/mkk5gqbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="qu7egmbzc"/><path clip-rule="evenodd" class="hmy4ymk6a"/><path class="mkk5gqbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:close-wifi" /></template>
