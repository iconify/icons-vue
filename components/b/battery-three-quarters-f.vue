<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itbu9wb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="itbu9wb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:battery-three-quarters-f" /></template>
