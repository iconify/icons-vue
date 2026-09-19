<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr7d6n9od.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xr7d6n9od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:caret-up-outline" /></template>
