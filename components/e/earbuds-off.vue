<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ust0jibvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ust0jibvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:earbuds-off" /></template>
