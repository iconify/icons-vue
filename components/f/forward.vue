<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks2idvyws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks2idvyws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:forward" /></template>
