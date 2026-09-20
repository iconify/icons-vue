<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vnbx2b2zx.css';
import '../../css/j/j8kuw0sgj.css';
import '../../css/f/fr98mpz8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vnbx2b2zx"/><path class="j8kuw0sgj"/><path clip-rule="evenodd" class="fr98mpz8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ghost-outline" /></template>
