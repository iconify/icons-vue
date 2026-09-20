<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1ztnb6x.css';
import '../../css/l/ldryaf89d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1ztnb6x"/><path class="ldryaf89d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bing-logo-bold" /></template>
