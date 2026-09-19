<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba0b0rtyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba0b0rtyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-2-light" /></template>
