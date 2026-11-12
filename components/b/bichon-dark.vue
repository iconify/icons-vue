<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaunbmwzy.css';
import '../../css/d/dsukp8ctc.css';
import '../../css/u/ubdlf3wbm.css';
import '../../css/l/l4hqxy0vi.css';
import '../../css/e/ee0qnmblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yaunbmwzy"/><path class="dsukp8ctc"/><path class="ubdlf3wbm"/><path class="l4hqxy0vi"/><path class="ee0qnmblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bichon-dark" /></template>
