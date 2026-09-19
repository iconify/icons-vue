<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g10yrmh8a.css';
import '../../css/r/rs61gez4m.css';
import '../../css/w/wn6nkdbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="g10yrmh8a"/><path class="rs61gez4m"/><path class="wn6nkdbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:foot-medium-dark" /></template>
