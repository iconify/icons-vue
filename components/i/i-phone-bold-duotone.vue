<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd06o6ovg.css';
import '../../css/u/ur40gui8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd06o6ovg"/><path class="ur40gui8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:i-phone-bold-duotone" /></template>
