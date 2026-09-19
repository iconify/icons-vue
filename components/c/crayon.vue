<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/flc0i3bca.css';
import '../../css/l/l8ko_sw9f.css';
import '../../css/f/fc6kyk_co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="flc0i3bca"/><path class="l8ko_sw9f"/><path class="fc6kyk_co"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:crayon" /></template>
