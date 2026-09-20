<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqft92biu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqft92biu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:key-skeleton-alt" /></template>
