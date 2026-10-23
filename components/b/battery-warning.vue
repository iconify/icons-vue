<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe_tb04fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe_tb04fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:battery-warning" /></template>
