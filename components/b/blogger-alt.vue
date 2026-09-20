<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_uuu056f.css';
import '../../css/q/qdis4za-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_uuu056f"/><path class="qdis4za-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:blogger-alt" /></template>
