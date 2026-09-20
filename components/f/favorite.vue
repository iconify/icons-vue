<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhyv_gnrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhyv_gnrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:favorite" /></template>
