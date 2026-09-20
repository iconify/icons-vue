<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmv0jrv6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmv0jrv6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:h2" /></template>
