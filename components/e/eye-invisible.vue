<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjqyt7b_n.css';
import '../../css/g/gi_7ztbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pjqyt7b_n"/><path class="gi_7ztbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eye-invisible" /></template>
