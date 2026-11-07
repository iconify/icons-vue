<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li7-h_b7c.css';
import '../../css/u/uq0t-hbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li7-h_b7c"/><path class="uq0t-hbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-bold-duotone" /></template>
