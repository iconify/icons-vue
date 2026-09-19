<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj0jtsbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jj0jtsbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:dollar-circle-solid" /></template>
