<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fk-xnnm5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk-xnnm5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:brush-cleaning" /></template>
