<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixdumrbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixdumrbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:keyframe-align-horizontal-filled" /></template>
