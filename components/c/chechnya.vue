<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksnmb0v6t.css';
import '../../css/y/ytckw3b9r.css';
import '../../css/l/lxia6g_nu.css';
import '../../css/o/ol-1x80it.css';
import '../../css/c/c8g8wzbbt.css';
import '../../css/q/q83zliwtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="ksnmb0v6t"/><path class="ytckw3b9r"/><path class="lxia6g_nu"/><path class="ol-1x80it"/><path class="c8g8wzbbt"/><path class="q83zliwtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:chechnya" /></template>
