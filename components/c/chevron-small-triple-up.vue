<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/b/bxli5t.css';
import '../../css/l/ln52_i.css';
import '../../css/f/fm8ssf.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c bxli5t"/><path class="a0m25c ln52_i"/><path class="a0m25c fm8ssf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-small-triple-up" /></template>
