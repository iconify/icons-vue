<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvnx57abk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnx57abk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:invoice-edit-outline" /></template>
