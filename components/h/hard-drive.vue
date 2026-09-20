<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psu7hxbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psu7hxbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:hard-drive" /></template>
