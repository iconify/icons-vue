<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gur--achi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gur--achi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:compare-filled" /></template>
