<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8e288bnc.css';
import '../../css/u/un6ua_l-y.css';
import '../../css/v/v4sg5jbkh.css';
import '../../css/z/zlv3p35br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v8e288bnc"/><path class="un6ua_l-y"/><path class="v4sg5jbkh"/><path class="zlv3p35br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-no-smoking" /></template>
