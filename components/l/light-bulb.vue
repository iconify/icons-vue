<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj95-5_rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj95-5_rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:light-bulb" /></template>
