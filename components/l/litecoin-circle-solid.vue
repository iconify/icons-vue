<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drqqs-5cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drqqs-5cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:litecoin-circle-solid" /></template>
