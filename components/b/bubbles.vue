<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/ecyiiytap.css';
import '../../css/q/qclwmq-1x.css';
import '../../css/b/bax3frbml.css';
import '../../css/d/dya2tw6rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ecyiiytap"/><circle class="qclwmq-1x"/><circle class="bax3frbml"/><path class="dya2tw6rb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bubbles" /></template>
