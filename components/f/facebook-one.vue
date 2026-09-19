<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s1hkfdcbz.css';
import '../../css/u/u5n_y8b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s1hkfdcbz"/><path class="u5n_y8b6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:facebook-one" /></template>
