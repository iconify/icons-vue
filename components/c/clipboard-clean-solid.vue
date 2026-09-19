<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l06u34vfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l06u34vfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-clean-solid" /></template>
