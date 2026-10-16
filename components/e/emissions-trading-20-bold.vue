<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2arlh74i.css';
import '../../css/g/gfbgo5b2g.css';
import '../../css/o/owlyunb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k2arlh74i"/><path class="gfbgo5b2g"/><path class="owlyunb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emissions-trading-20-bold" /></template>
