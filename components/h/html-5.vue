<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9kaghb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9kaghb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:html-5" /></template>
