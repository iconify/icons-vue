<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w9jvul8en.css';
import '../../css/l/l6a3mob9c.css';
import '../../css/d/d2vzwr-fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="w9jvul8en"/><path class="l6a3mob9c"/><path class="d2vzwr-fl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:book-check-duotone" /></template>
