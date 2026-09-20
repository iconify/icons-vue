<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k73k7yq-m.css';
import '../../css/u/u79pk-b6p.css';
import '../../css/k/k74euduoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k73k7yq-m"/><path class="u79pk-b6p"/><path class="k74euduoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-text-add-bold" /></template>
