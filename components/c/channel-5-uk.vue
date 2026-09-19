<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3rh6sb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3rh6sb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:channel-5-uk" /></template>
