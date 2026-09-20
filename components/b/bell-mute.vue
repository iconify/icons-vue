<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvs0_tbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvs0_tbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:bell-mute" /></template>
