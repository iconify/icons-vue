<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efikpikom.css';
import '../../css/v/vsc753i0a.css';
import '../../css/b/bgs0obc3p.css';
import '../../css/i/izmb9h44l.css';
import '../../css/r/rub2ksxch.css';
import '../../css/m/mo88tmbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="efikpikom"/><path class="vsc753i0a"/><path class="bgs0obc3p"/><path class="izmb9h44l"/><path class="rub2ksxch"/><path class="mo88tmbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discourse" /></template>
