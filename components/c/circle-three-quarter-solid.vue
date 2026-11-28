<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd68rr0ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd68rr0ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-three-quarter-solid" /></template>
