<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ignec6b8h.css';
import '../../css/e/edgg_m-zr.css';
import '../../css/e/eyrktq3-q.css';
import '../../css/l/lo6d6knyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ignec6b8h"/><path class="edgg_m-zr"/><path class="eyrktq3-q"/><path class="lo6d6knyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:eritrea" /></template>
