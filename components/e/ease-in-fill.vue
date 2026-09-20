<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa4_z_bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qa4_z_bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ease-in-fill" /></template>
