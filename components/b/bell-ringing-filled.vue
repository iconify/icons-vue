<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unp_oacth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unp_oacth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bell-ringing-filled" /></template>
