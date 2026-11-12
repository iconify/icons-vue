<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pojcwywxn.css';
import '../../css/h/hua_nkb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pojcwywxn"/><path class="hua_nkb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gathio-dark" /></template>
