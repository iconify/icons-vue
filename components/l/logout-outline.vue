<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl4lbdb9f.css';
import '../../css/g/g1x_1bbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl4lbdb9f"/><path class="g1x_1bbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-outline" /></template>
