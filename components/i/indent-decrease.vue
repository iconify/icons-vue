<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/n1qktjb3p.css';
import '../../css/t/txjglpbqa.css';
import '../../css/s/sfhxn_bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="n1qktjb3p wm-shadow"/><path class="txjglpbqa wm-shadow"/><path class="sfhxn_bcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:indent-decrease" /></template>
