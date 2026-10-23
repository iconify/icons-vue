<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxv2ymz5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxv2ymz5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:archive-x" /></template>
