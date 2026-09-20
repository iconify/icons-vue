<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx-x791iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx-x791iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-down-large-duotone" /></template>
