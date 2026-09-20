<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfo-imd_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfo-imd_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:cloudcannon" /></template>
