<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir38ubcvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir38ubcvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:info-octagon-filled" /></template>
