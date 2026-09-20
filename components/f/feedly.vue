<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdc-kyntd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdc-kyntd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:feedly" /></template>
