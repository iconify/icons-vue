<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/d/dza1eb.css';
import '../../css/z/z9_d1p.css';
import '../../css/s/so-from-18.css';
import '../../css/t/tr-2c6-rw.css';
import '../../css/s/so-from-60.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c dza1eb"/><path class="a0m25c z9_d1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:loading-twotone-loop" /></template>
