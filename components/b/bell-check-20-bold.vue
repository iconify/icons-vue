<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w79r3bb5w.css';
import '../../css/b/btzvfmb9o.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w79r3bb5w"/><path class="btzvfmb9o"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-check-20-bold" /></template>
