<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f65x4gbxw.css';
import '../../css/w/w1jc-qglq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f65x4gbxw"/><path class="w1jc-qglq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:inbox" /></template>
