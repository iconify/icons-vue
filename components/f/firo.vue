<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu2ow8bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu2ow8bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:firo" /></template>
