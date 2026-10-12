<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ysx9685wi.css';
import '../../css/y/yx115lobs.css';
import '../../css/c/c4jqm5b5v.css';
import '../../css/r/rhwrewb6n.css';
import '../../css/l/lzmnrrp8b.css';
import '../../css/m/mxz5qbb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ysx9685wi"/><path class="yx115lobs"/><path class="c4jqm5b5v"/><path class="rhwrewb6n"/><path class="lzmnrrp8b"/><path class="mxz5qbb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-tank-x-20" /></template>
