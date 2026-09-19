<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf3axfyug.css';
import '../../css/i/ikmyx1evo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="hf3axfyug"/><path clip-rule="evenodd" class="ikmyx1evo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:laravel" /></template>
