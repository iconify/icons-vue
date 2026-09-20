<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/gl9wosb7m.css';
import '../../css/r/r_1f29b9n.css';
import '../../css/o/oomb74bzs.css';
import '../../css/c/cx0jtacae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gl9wosb7m"/><path class="r_1f29b9n"/><path class="oomb74bzs"/><path class="cx0jtacae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-broken" /></template>
