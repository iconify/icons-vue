<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmw38b5pn.css';
import '../../css/z/zse_r2bij.css';
import '../../css/c/cs-uxhb8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmw38b5pn"/><path class="zse_r2bij"/><circle class="cs-uxhb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flashlight" /></template>
