<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv0b3shvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vv0b3shvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:airplay" /></template>
