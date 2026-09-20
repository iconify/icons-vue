<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey9koeo-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey9koeo-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kubespray" /></template>
