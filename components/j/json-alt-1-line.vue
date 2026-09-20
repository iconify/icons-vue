<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obkeojb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obkeojb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:json-alt-1-line" /></template>
