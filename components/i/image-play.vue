<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kgo6dpbjf.css';
import '../../css/s/sx6hnebpa.css';
import '../../css/k/krh2erb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kgo6dpbjf"/><path class="sx6hnebpa"/><path class="krh2erb9t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:image-play" /></template>
