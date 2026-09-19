<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy5jeenne.css';
import '../../css/t/tkw3w5bpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cy5jeenne"/><path class="tkw3w5bpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:build-twotone" /></template>
