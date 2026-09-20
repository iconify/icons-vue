<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayrxfubgw.css';
import '../../css/b/b8neo7vhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ayrxfubgw"/><path class="b8neo7vhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:credit-card" /></template>
