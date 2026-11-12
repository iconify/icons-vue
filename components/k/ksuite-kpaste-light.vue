<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deg8ao8ms.css';
import '../../css/p/piysc6sno.css';
import '../../css/c/c3vcymbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="deg8ao8ms"/><path class="piysc6sno"/><path class="c3vcymbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kpaste-light" /></template>
