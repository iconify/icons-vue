<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcv3qbcsb.css';
import '../../css/z/zq4712bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":269.567,"height":153.532};
const content = `<path class="kcv3qbcsb"/><path class="zq4712bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amazon-fire-tv" /></template>
