<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meuuvccta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="meuuvccta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-right-16-solid" /></template>
