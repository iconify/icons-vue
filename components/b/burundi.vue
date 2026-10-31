<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niuelpbca.css';
import '../../css/h/hsgjtibkt.css';
import '../../css/e/e-xmbx7qy.css';
import '../../css/v/vjl19yb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="niuelpbca"/><path class="hsgjtibkt"/><path class="e-xmbx7qy"/><path class="vjl19yb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:burundi" /></template>
