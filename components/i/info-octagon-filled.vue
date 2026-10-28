<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxls-hb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxls-hb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:info-octagon-filled" /></template>
