<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cb5k0fb4e.css';
import '../../css/q/qglu0sgat.css';
import '../../css/w/w379rftri.css';
import '../../css/x/xn2m8zz0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cb5k0fb4e"/><rect class="qglu0sgat"/><rect class="w379rftri"/><rect class="xn2m8zz0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:grid" /></template>
