<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lqqsiww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3lqqsiww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dart" /></template>
