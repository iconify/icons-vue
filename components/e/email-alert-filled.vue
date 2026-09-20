<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk17ct.css';
import '../../css/a/a0m25c.css';
import '../../css/e/eup04y.css';
import '../../css/g/g2ouze.css';
import '../../css/p/pl-mjc.css';
import '../../css/x/xxwxit.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk17ct"/><path class="a0m25c eup04y"/><path class="a0m25c g2ouze"/><path class="a0m25c pl-mjc"/><path class="a0m25c xxwxit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:email-alert-filled" /></template>
