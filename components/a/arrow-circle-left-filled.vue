<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vek3s5bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vek3s5bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-circle-left-filled" /></template>
