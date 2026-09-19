<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyguhx2tf.css';
import '../../css/z/zme4g8b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cyguhx2tf"/><path class="zme4g8b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-vpn-for-vpc" /></template>
