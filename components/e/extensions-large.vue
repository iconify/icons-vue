<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si18as_vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si18as_vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:extensions-large" /></template>
