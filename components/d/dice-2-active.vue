<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy-z_rbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gy-z_rbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-2-active" /></template>
