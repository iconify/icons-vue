<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tz70rrb9c.css';
import '../../css/s/sbf0mdb_x.css';
import '../../css/k/ksody8b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tz70rrb9c"/><path class="sbf0mdb_x"/><path class="ksody8b7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-remove-01" /></template>
