<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyd5-obni.css';
import '../../css/t/th32pl67c.css';
import '../../css/q/q_2n7obtj.css';
import '../../css/z/zvgjxlbcx.css';
import '../../css/b/betwnjbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyd5-obni"/><path class="th32pl67c"/><path class="q_2n7obtj"/><path class="zvgjxlbcx"/><path class="betwnjbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-domains" /></template>
