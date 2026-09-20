<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s282eramm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s282eramm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bread-filled" /></template>
