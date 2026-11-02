<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbn6y9b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbn6y9b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flight-inflight-line" /></template>
