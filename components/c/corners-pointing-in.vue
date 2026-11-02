<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxo39ibgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxo39ibgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:corners-pointing-in" /></template>
