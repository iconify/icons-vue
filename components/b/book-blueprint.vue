<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yukf-6eye.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/h/ht3319b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yukf-6eye"/><path class="rbzq4bjzv wm-deco"/><path class="ht3319b2c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-blueprint" /></template>
