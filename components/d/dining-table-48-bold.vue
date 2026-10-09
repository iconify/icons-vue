<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyyqc0_4u.css';
import '../../css/l/lt5eqobgu.css';
import '../../css/b/bm1mepbat.css';
import '../../css/t/tm8mwlb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyyqc0_4u"/><path class="lt5eqobgu"/><path class="bm1mepbat"/><path class="tm8mwlb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:dining-table-48-bold" /></template>
