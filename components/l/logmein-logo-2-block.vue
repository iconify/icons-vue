<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrbyutbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrbyutbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:logmein-logo-2-block" /></template>
