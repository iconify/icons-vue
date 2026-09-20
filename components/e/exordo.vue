<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuygxqbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuygxqbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:exordo" /></template>
