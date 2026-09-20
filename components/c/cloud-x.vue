<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi9vhsedn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yi9vhsedn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-x" /></template>
