<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfe_wvkpo.css';
import '../../css/t/t3678pb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfe_wvkpo"/><path class="t3678pb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:code-block-solid" /></template>
