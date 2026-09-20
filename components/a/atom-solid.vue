<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnfhb-bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnfhb-bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:atom-solid" /></template>
