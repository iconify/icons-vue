<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o89xl2b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o89xl2b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dna-2-off" /></template>
