<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kid2_mgyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kid2_mgyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:command-line" /></template>
