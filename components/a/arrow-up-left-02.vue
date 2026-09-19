<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4sf2jbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4sf2jbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-left-02" /></template>
