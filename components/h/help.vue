<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svuxsywhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svuxsywhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:help" /></template>
