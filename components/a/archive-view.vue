<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lejv3lbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lejv3lbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-view" /></template>
