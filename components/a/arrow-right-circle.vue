<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/p0bift.css';
import '../../css/j/j4_0cv.css';
import '../../css/b/b46h1j.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c p0bift"/><path class="a0m25c j4_0cv"/><path class="a0m25c b46h1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-right-circle" /></template>
