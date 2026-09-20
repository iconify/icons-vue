<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbr937byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbr937byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-off" /></template>
