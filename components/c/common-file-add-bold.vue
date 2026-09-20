<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcglrybdp.css';
import '../../css/k/k74euduoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcglrybdp"/><path class="k74euduoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-add-bold" /></template>
