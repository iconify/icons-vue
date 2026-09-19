<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fld8c3bto.css';
import '../../css/d/dk0jq69yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fld8c3bto"/><path clip-rule="evenodd" class="dk0jq69yo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:cash-register-solid" /></template>
