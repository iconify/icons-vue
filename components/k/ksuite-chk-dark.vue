<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykqjh5npp.css';
import '../../css/t/tvigq4bta.css';
import '../../css/l/lspatcbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ykqjh5npp"/><path class="tvigq4bta"/><path class="lspatcbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-chk-dark" /></template>
