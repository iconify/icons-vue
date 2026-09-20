<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzqw7kbmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzqw7kbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:liquibase" /></template>
