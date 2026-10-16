<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9_awgbuo.css';
import '../../css/b/bs4b6zbqx.css';
import '../../css/i/ikg91lbvs.css';
import '../../css/d/d9cmlutdo.css';
import '../../css/j/j2lc92b5l.css';
import '../../css/o/onos5bcao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":370.5,"height":362,"left":-5.38,"top":-1.13};
const content = `<path class="f9_awgbuo"/><path class="bs4b6zbqx"/><path class="ikg91lbvs"/><path class="d9cmlutdo"/><path class="j2lc92b5l"/><path class="onos5bcao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cri-o-dark" /></template>
