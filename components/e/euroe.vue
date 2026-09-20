<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuoui0bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuoui0bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:euroe" /></template>
