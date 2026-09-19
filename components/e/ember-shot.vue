<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eic0nhb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eic0nhb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ember-shot" /></template>
