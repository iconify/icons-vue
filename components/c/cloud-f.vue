<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peqpa-bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="peqpa-bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:cloud-f" /></template>
