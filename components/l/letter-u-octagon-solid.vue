<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wytsss47o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wytsss47o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u-octagon-solid" /></template>
