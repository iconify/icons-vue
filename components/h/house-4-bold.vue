<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_n8q2b0o.css';
import '../../css/n/nmzc2_bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_n8q2b0o"/><path class="nmzc2_bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:house-4-bold" /></template>
