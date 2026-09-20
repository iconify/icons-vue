<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-3k_lb1q.css';
import '../../css/a/a0u305bhu.css';
import '../../css/e/ewy3v6o-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-3k_lb1q"/><path class="a0u305bhu"/><path class="ewy3v6o-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bdp" /></template>
