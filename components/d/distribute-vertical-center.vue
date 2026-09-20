<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4kttc2nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4kttc2nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:distribute-vertical-center" /></template>
