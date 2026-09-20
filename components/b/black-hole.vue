<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m8jnzqbdy.css';
import '../../css/h/hyih-4b5l.css';
import '../../css/l/ledvo0j9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="m8jnzqbdy"/><path clip-rule="evenodd" class="hyih-4b5l"/><path clip-rule="evenodd" class="ledvo0j9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:black-hole" /></template>
