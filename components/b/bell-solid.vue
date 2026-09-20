<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc49n6q0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc49n6q0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bell-solid" /></template>
