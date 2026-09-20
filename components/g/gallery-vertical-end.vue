<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_afs-7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp_afs-7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gallery-vertical-end" /></template>
