<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffby4cb3r.css';
import '../../css/m/m14k5zb3c.css';
import '../../css/o/o-vb-yaor.css';
import '../../css/m/ml0-2dt_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ffby4cb3r"/><path class="m14k5zb3c"/><path class="o-vb-yaor"/><path class="ml0-2dt_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:flood-warning" /></template>
