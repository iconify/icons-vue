<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qszh7vb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qszh7vb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-russian-ruble-solid" /></template>
