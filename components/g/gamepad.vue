<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i29ic5bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i29ic5bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:gamepad" /></template>
