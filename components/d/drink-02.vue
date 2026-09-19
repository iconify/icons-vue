<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqf2av3eh.css';
import '../../css/g/gzb59-bvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqf2av3eh"/><path class="gzb59-bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:drink-02" /></template>
