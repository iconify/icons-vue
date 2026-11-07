<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kswv2hrkj.css';
import '../../css/m/mqmycj9zd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kswv2hrkj"/><path class="mqmycj9zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-off-bold-duotone" /></template>
