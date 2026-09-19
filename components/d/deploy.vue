<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8_9mnbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8_9mnbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:deploy" /></template>
