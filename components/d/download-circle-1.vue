<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxm40qhvn.css';
import '../../css/a/alf2ikb1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="lxm40qhvn"/><path clip-rule="evenodd" class="alf2ikb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:download-circle-1" /></template>
