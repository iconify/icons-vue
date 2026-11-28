<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_s4wsb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_s4wsb7p primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cloud-off-duotone" /></template>
