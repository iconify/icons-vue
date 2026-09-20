<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9-5mhb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9-5mhb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cloud-offline-24" /></template>
