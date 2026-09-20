<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm31op6ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qm31op6ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-logo-solid" /></template>
