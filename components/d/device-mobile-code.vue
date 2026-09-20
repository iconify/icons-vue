<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g54wtuskx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g54wtuskx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-code" /></template>
