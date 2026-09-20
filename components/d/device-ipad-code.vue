<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q21sykgee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q21sykgee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-code" /></template>
