<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aa9di2ohz.css';
import '../../css/c/c7oif2b9e.css';
import '../../css/p/pfl1vrb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aa9di2ohz"/><path class="c7oif2b9e"/><path class="pfl1vrb9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-down-za" /></template>
