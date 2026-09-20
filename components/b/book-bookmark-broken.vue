<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t-007b-3c.css';
import '../../css/f/fx38fz2eg.css';
import '../../css/d/dmzio9b4p.css';
import '../../css/p/paayxvxde.css';
import '../../css/l/lyw4o5ucl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t-007b-3c"/><path class="fx38fz2eg"/><path class="dmzio9b4p"/><path class="paayxvxde"/><path class="lyw4o5ucl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-bookmark-broken" /></template>
