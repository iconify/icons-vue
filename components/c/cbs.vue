<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz3hkdpne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz3hkdpne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cbs" /></template>
