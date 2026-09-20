<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbjg4bc7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjg4bc7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crown-solid" /></template>
