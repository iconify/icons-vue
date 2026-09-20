<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd9fl7typ.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd9fl7typ"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:code-circle-filled" /></template>
