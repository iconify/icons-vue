<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/u/umd-9o.css';
import '../../css/d/dzrx5u.css';
import '../../css/p/pfrmhe.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c umd-9o"/><path class="a0m25c dzrx5u"/><path class="a0m25c pfrmhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-close-left" /></template>
