<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/v/v9myf9bmx.css';
import '../../css/p/pdzzspcnx.css';
import '../../css/p/p26y3yb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="v9myf9bmx"/><circle class="pdzzspcnx"/><path class="p26y3yb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-dock-search-light" /></template>
