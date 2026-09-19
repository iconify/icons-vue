<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1pu1rrxi.css';
import '../../css/g/gmc9imcga.css';
import '../../css/y/y192wnsah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j1pu1rrxi"/><path class="gmc9imcga"/><path class="y192wnsah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:html5-twotone" /></template>
