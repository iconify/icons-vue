<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/g/gnn5qpboc.css';
import '../../css/n/nqxm3wozy.css';
import '../../css/i/i2onpmbub.css';
import '../../css/u/u5ygvwb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="gnn5qpboc wm-shadow"/><path class="nqxm3wozy wm-shadow"/><path class="i2onpmbub"/><path class="u5ygvwb3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:arrow-left-to-line" /></template>
