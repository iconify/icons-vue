<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/v0zg4ab8h.css';
import '../../css/y/ya5guhb6t.css';
import '../../css/i/ixl_lxadt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="v0zg4ab8h"/><path class="ya5guhb6t"/><path class="ixl_lxadt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:magnet" /></template>
