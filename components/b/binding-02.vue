<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq_plobvb.css';
import '../../css/x/xidavd7kn.css';
import '../../css/r/rfqd2w1ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gq_plobvb"/><path class="xidavd7kn"/><path class="rfqd2w1ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:binding-02" /></template>
