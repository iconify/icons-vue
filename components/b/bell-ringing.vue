<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba3_y3ujc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba3_y3ujc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-ringing" /></template>
