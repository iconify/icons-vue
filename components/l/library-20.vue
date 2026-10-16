<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ni6vb5b.css';
import '../../css/e/edo682exk.css';
import '../../css/a/atrqkbbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="edo682exk"/><path class="atrqkbbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:library-20" /></template>
