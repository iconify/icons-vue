<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2p352fxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o2p352fxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:charging-station" /></template>
