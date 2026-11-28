<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drijd_0ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drijd_0ya primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:herb-duotone" /></template>
