<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt_mgpbid.css';
import '../../css/o/o6nn443db.css';
import '../../css/v/v_kq-2bzc.css';
import '../../css/q/qqog5e9wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vt_mgpbid"/><path class="o6nn443db"/><path class="v_kq-2bzc"/><path class="qqog5e9wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:earofmaize" /></template>
