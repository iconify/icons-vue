<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9ttgzwoy.css';
import '../../css/a/a9r0l3bpj.css';
import '../../css/p/pq5d4i-df.css';
import '../../css/c/csl8dlbrs.css';
import '../../css/r/rjunq3ykp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z9ttgzwoy"/><path class="a9r0l3bpj wm-a"/><path class="pq5d4i-df wm-k"/><path class="csl8dlbrs wm-k"/><path class="rjunq3ykp wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:alarm-clock" /></template>
