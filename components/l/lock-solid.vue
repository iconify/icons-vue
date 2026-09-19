<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dip1b8dgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dip1b8dgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lock-solid" /></template>
