<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cetpj1bqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cetpj1bqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:book" /></template>
