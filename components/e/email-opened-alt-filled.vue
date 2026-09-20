<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt5c4z.css';
import '../../css/a/a0m25c.css';
import '../../css/o/ofn98h.css';
import '../../css/n/nrq0xo.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt5c4z"/><path class="a0m25c ofn98h"/><path class="a0m25c nrq0xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:email-opened-alt-filled" /></template>
