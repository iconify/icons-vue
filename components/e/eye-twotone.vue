<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwwc2ab5u.css';
import '../../css/x/xfn8r9bjr.css';
import '../../css/f/fma9jpbyl.css';
import '../../css/t/t4em2zgug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cwwc2ab5u"/><path class="xfn8r9bjr"/><path class="fma9jpbyl"/><path class="t4em2zgug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:eye-twotone" /></template>
