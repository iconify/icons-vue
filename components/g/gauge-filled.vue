<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/narou_78v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="narou_78v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gauge-filled" /></template>
