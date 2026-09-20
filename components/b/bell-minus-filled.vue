<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wclhac05w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wclhac05w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-minus-filled" /></template>
