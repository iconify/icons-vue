<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx9qdackm.css';
import '../../css/e/eai2o3bto.css';
import '../../css/i/i2tovxbyl.css';
import '../../css/n/na412xbqh.css';
import '../../css/t/t210tybnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx9qdackm"/><path class="eai2o3bto"/><path class="i2tovxbyl"/><path class="na412xbqh"/><path class="t210tybnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:data-qna" /></template>
