<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui6oo4bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui6oo4bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:magnify-minus-outline" /></template>
