<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdlmu3blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="sdlmu3blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:backspace-solid" /></template>
