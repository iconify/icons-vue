<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovp2rs4mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovp2rs4mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dumpling-filled" /></template>
