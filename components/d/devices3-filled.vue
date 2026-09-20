<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8u9m_bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8u9m_bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:devices3-filled" /></template>
