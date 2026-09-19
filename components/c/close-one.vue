<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/k/kgsb8exge.css';
import '../../css/q/qu2te6grh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="kgsb8exge"/><path class="qu2te6grh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:close-one" /></template>
