<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ei7tbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v9ei7tbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:azero" /></template>
