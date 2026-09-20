<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ok5lcfjri.css';
import '../../css/l/lt7j86jjt.css';
import '../../css/c/cz_7jaczd.css';
import '../../css/l/l6md27rub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ok5lcfjri"/><path class="lt7j86jjt"/><path class="cz_7jaczd"/><path class="l6md27rub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fog-linear" /></template>
