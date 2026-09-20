<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugcq4-b9s.css';
import '../../css/s/s-czd34rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":82.6,"height":82.6};
const content = `<circle class="ugcq4-b9s"/><path class="s-czd34rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:litecoin" /></template>
