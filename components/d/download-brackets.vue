<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vf-k8abmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vf-k8abmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:download-brackets" /></template>
