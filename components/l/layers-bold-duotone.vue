<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3vb0177b.css';
import '../../css/n/nvazcab2q.css';
import '../../css/l/lh00_hb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3vb0177b"/><path class="nvazcab2q"/><path class="lh00_hb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:layers-bold-duotone" /></template>
