<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj-o9e.css';
import '../../css/a/a0m25c.css';
import '../../css/r/rmjj0t.css';
import '../../css/y/yqwu-f.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-from-16.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj-o9e"/><path class="a0m25c rmjj0t"/><path class="a0m25c yqwu-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:heart-half-filled" /></template>
