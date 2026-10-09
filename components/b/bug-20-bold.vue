<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcy6jh_of.css';
import '../../css/r/rx-p80tpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lcy6jh_of"/><path class="rx-p80tpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bug-20-bold" /></template>
