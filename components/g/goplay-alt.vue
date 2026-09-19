<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shl10mbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shl10mbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:goplay-alt" /></template>
