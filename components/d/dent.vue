<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p60eapvkt.css';
import '../../css/p/pqzlykbsi.css';
import '../../css/r/r306avbbq.css';
import '../../css/r/r7fu50bys.css';
import '../../css/d/dr9i5ncll.css';
import '../../css/l/lie1g2bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p60eapvkt"/><path class="pqzlykbsi"/><path class="r306avbbq"/><path class="r7fu50bys"/><path class="dr9i5ncll"/><path class="lie1g2bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dent" /></template>
