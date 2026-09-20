<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v22x25v2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v22x25v2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-pause" /></template>
