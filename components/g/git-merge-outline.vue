<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgrlpfb5w.css';
import '../../css/n/nm7yi4b_v.css';
import '../../css/n/npaoi6s8i.css';
import '../../css/e/ezv6ukqwd.css';
import '../../css/f/fi82jxbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="xgrlpfb5w"/><circle class="nm7yi4b_v"/><path class="npaoi6s8i"/><circle class="ezv6ukqwd"/><path class="fi82jxbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:git-merge-outline" /></template>
