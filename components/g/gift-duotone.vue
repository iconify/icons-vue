<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/krtu-13-w.css';
import '../../css/x/xpoj7wbil.css';
import '../../css/h/hn0gbhbid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="krtu-13-w"/><path class="xpoj7wbil"/><path class="hn0gbhbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gift-duotone" /></template>
