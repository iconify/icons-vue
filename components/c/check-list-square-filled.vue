<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0_z9mbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n0_z9mbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:check-list-square-filled" /></template>
