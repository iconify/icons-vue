<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgiwjsz1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgiwjsz1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-outgoing-02" /></template>
