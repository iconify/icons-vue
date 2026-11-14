<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qhsvm2ywy.css';
import '../../css/g/ghrqsmb5n.css';
import '../../css/g/g6vnjnbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qhsvm2ywy"/><path class="ghrqsmb5n"/><path class="g6vnjnbpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:community-verified" /></template>
