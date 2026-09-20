<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcduzqdcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcduzqdcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-align-center-filled" /></template>
