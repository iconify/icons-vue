<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n_8he5btp.css';
import '../../css/a/axjnae9lz.css';
import '../../css/n/n6lorqbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n_8he5btp"/><path class="axjnae9lz"/><path class="n6lorqbqf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drum-duotone" /></template>
