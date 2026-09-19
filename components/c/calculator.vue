<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckynhstji.css';
import '../../css/k/ks6oztbqd.css';
import '../../css/s/sauh1_b3m.css';
import '../../css/j/j9g66rbzl.css';
import '../../css/z/z04d4fg2q.css';
import '../../css/q/qbybt8bhi.css';
import '../../css/k/kwxad432l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ckynhstji"/><path class="ks6oztbqd"/><path class="sauh1_b3m"/><path class="j9g66rbzl"/><path class="z04d4fg2q"/><path class="qbybt8bhi"/><path class="kwxad432l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:calculator" /></template>
