<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3-xsrb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3-xsrb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:direct-right-filled" /></template>
