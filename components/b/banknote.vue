<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf7nan7si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf7nan7si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banknote" /></template>
