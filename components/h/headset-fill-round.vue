<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnts40jnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnts40jnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headset-fill-round" /></template>
