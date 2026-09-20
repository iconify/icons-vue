<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/r9fx9tx9u.css';
import '../../css/d/dzrc8rb0x.css';
import '../../css/j/jq-afy2wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r9fx9tx9u"/><path class="dzrc8rb0x"/><path class="jq-afy2wo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-user" /></template>
