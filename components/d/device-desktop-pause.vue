<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar3k3kbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar3k3kbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-desktop-pause" /></template>
