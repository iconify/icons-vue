<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bufq13isk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bufq13isk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-activity-sharp-fill" /></template>
