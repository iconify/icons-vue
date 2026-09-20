<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsr4q-iac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsr4q-iac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:feel-at-ease-filled" /></template>
