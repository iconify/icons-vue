<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbr_9nbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr_9nbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:criterion-channel" /></template>
