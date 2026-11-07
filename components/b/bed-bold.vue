<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdcb-2svx.css';
import '../../css/d/dod872beq.css';
import '../../css/g/g15r-phwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdcb-2svx"/><path class="dod872beq"/><path clip-rule="evenodd" class="g15r-phwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bed-bold" /></template>
