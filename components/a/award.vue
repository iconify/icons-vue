<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eig_suvqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eig_suvqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:award" /></template>
