<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg5dp-llk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5dp-llk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aorus" /></template>
