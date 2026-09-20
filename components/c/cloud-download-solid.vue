<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6sn_6h4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6sn_6h4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cloud-download-solid" /></template>
