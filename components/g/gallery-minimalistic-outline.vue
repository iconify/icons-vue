<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfv_stdde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfv_stdde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-minimalistic-outline" /></template>
