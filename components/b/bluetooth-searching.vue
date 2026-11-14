<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iefp4vbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iefp4vbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bluetooth-searching" /></template>
