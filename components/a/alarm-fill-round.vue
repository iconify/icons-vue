<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md5jwx3_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md5jwx3_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-fill-round" /></template>
