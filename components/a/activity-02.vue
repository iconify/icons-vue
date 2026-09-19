<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jr7vbsb8z.css';
import '../../css/c/cgdrp4m5c.css';
import '../../css/o/o45vqq0ds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jr7vbsb8z"/><path class="cgdrp4m5c"/><path class="o45vqq0ds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:activity-02" /></template>
