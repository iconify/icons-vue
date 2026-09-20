<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag36mlbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag36mlbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-full" /></template>
