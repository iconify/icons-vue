<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smj7c3byz.css';
import '../../css/i/ir3eif-7d.css';
import '../../css/v/vj4ug-bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="smj7c3byz"/><path class="ir3eif-7d"/><path class="vj4ug-bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bosnia-and-herzegovina" /></template>
