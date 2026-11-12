<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9a_esbwi.css';
import '../../css/s/sk-8-kkto.css';
import '../../css/w/we___fbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a9a_esbwi"/><path class="sk-8-kkto"/><path class="we___fbjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-contacts-light" /></template>
