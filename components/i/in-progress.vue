<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qglvkk1rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qglvkk1rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:in-progress" /></template>
