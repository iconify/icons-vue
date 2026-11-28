<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgtz7qjon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgtz7qjon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:banknote-check" /></template>
