<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hyjon0btb.css';
import '../../css/t/t1in8db2h.css';
import '../../css/s/s41he0bba.css';
import '../../css/m/m-5zcvb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hyjon0btb"/><path class="t1in8db2h"/><path class="s41he0bba"/><path class="m-5zcvb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-linear" /></template>
