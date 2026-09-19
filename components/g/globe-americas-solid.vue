<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sljfn47mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sljfn47mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-americas-solid" /></template>
