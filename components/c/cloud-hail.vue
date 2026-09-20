<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlaksp4ow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlaksp4ow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-hail" /></template>
