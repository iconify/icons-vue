<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1gso4b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1gso4b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-medical" /></template>
