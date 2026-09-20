<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jwz7e6b-q.css';
import '../../css/t/tbfod3hgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jwz7e6b-q"/><rect class="tbfod3hgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-right-square" /></template>
