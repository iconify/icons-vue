<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkg302pkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkg302pkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:lightning-slash" /></template>
