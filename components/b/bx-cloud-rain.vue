<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-yt7ibsl.css';
import '../../css/m/mfa8tygij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-yt7ibsl"/><path class="mfa8tygij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-cloud-rain" /></template>
