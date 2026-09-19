<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz93zk_kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="zz93zk_kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:largebluecircle" /></template>
