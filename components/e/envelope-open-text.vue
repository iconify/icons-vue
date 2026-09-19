<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdl45rbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mdl45rbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:envelope-open-text" /></template>
