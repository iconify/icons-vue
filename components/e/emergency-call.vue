<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3osa8bkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3osa8bkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:emergency-call" /></template>
