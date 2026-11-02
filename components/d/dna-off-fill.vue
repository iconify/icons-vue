<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdpnaib3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdpnaib3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dna-off-fill" /></template>
