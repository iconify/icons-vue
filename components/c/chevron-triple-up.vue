<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/k/koytqz.css';
import '../../css/w/wre3wa.css';
import '../../css/g/gw0cej.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c koytqz"/><path class="a0m25c wre3wa"/><path class="a0m25c gw0cej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:chevron-triple-up" /></template>
