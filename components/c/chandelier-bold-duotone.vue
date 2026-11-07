<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv5nl_bjz.css';
import '../../css/y/yq0r6kchx.css';
import '../../css/h/hp-w9zbfb.css';
import '../../css/o/oyw1l7bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pv5nl_bjz"/><path class="yq0r6kchx"/><path class="hp-w9zbfb"/><path class="oyw1l7bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chandelier-bold-duotone" /></template>
