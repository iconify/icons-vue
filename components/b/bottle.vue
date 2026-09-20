<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h55yyx4bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h55yyx4bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bottle" /></template>
