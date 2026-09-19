<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl3ctjb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sl3ctjb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bed-linen-filled" /></template>
