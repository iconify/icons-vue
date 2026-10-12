<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nmzcp8s6h.css';
import '../../css/p/pnxg1kyll.css';
import '../../css/w/whl5lnb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nmzcp8s6h"/><path class="pnxg1kyll"/><path class="whl5lnb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:door-closed-locked-duotone" /></template>
