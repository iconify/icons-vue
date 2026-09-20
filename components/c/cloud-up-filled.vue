<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2oo-pb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2oo-pb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cloud-up-filled" /></template>
