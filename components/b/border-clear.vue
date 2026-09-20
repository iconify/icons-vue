<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4dpc3bro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dpc3bro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:border-clear" /></template>
