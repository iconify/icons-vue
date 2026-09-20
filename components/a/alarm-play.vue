<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh90i4ezv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh90i4ezv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm-play" /></template>
