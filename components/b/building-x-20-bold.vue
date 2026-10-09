<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqsj93biv.css';
import '../../css/n/ncybe8mrd.css';
import '../../css/f/fk_ahtbzo.css';
import '../../css/b/b325a1bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wqsj93biv"/><path class="ncybe8mrd"/><path class="fk_ahtbzo"/><path class="b325a1bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:building-x-20-bold" /></template>
