<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/r/r43dgsbqa.css';
import '../../css/s/sgmbzabxq.css';
import '../../css/s/sgxw2e1xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="r43dgsbqa"/><path class="sgmbzabxq"/><path class="sgxw2e1xb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:headphones" /></template>
