<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/z/zu019c.css';
import '../../css/z/zf6m_y.css';
import '../../css/r/rb0cwy.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c zu019c"/><path class="a0m25c zf6m_y"/><path class="a0m25c rb0cwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-triple-right" /></template>
