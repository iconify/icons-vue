<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuutoabwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vuutoabwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:chat-bubble-2" /></template>
