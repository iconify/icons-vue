<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_mcmiblg.css';
import '../../css/y/y73gmufio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_mcmiblg"/><path class="y73gmufio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:application-instance-outlined" /></template>
