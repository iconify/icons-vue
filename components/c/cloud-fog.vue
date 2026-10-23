<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcvqu-9ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcvqu-9ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-fog" /></template>
