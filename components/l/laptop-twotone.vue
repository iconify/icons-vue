<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw1iew.css';
import '../../css/x/x6dwuo.css';
import '../../css/a/ahcaho.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-50.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew x6dwuo"/><path class="ahcaho iw1iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:laptop-twotone" /></template>
