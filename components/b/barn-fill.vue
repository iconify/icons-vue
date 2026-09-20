<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgbi-149m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qgbi-149m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:barn-fill" /></template>
