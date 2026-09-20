<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phg1s7mys.css';
import '../../css/a/a35dc2b9v.css';
import '../../css/b/b681yhxlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="phg1s7mys"/><path class="a35dc2b9v"/><path class="b681yhxlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ente-locker-dark" /></template>
