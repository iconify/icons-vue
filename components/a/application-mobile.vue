<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-qmbybjd.css';
import '../../css/z/z8okc2lzd.css';
import '../../css/k/k12ktmbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-qmbybjd"/><circle class="z8okc2lzd"/><path class="k12ktmbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:application-mobile" /></template>
