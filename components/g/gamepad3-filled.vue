<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzab_8mca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uzab_8mca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad3-filled" /></template>
