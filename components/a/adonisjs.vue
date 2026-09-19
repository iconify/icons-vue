<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-2tvnb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="n-2tvnb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:adonisjs" /></template>
