<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr3giu5xn.css';
import '../../css/c/ca34baqxh.css';
import '../../css/l/l56nfhv6e.css';
import '../../css/w/wwhv9711a.css';
import '../../css/b/b0cmkdksn.css';
import '../../css/b/bxqj37btp.css';
import '../../css/s/sewtzbcfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":73,"height":88};
const content = `<path class="qr3giu5xn"/><path class="ca34baqxh"/><path class="l56nfhv6e"/><circle class="wwhv9711a"/><circle class="b0cmkdksn"/><circle class="bxqj37btp"/><path class="sewtzbcfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:eps-file" /></template>
