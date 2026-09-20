<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbv1_z37o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbv1_z37o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-octagon" /></template>
