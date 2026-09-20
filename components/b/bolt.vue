<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0u1h5bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0u1h5bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bolt" /></template>
