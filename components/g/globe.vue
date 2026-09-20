<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h62bnzbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h62bnzbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:globe" /></template>
