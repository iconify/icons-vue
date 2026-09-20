<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlh2t63ch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlh2t63ch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:lines-list" /></template>
