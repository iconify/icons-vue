<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve3a99k9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve3a99k9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fresh" /></template>
