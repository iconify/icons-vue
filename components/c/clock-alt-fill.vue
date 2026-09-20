<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc-lvac0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc-lvac0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clock-alt-fill" /></template>
