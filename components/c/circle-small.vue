<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orle7obbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="orle7obbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-small" /></template>
