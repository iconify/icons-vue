<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqveb-bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqveb-bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-left" /></template>
