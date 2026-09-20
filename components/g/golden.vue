<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk7p9p4ic.css';
import '../../css/d/dj_nl9bot.css';
import '../../css/i/i0zetk6vj.css';
import '../../css/l/loe7u9xjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk7p9p4ic"/><path class="dj_nl9bot"/><path class="i0zetk6vj"/><path class="loe7u9xjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:golden" /></template>
