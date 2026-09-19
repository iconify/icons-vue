<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mcqdwpbfu.css';
import '../../css/v/v-kdjsb9r.css';
import '../../css/e/ecbdqbjip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mcqdwpbfu"/><path clip-rule="evenodd" class="v-kdjsb9r"/><path class="ecbdqbjip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-pig" /></template>
