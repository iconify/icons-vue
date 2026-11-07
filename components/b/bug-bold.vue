<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3q7gcrgc.css';
import '../../css/z/zheflh_st.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3q7gcrgc"/><path class="zheflh_st"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-bold" /></template>
