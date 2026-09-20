<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc6ttac-i.css';
import '../../css/k/kysr9_zzg.css';
import '../../css/x/x0ucnnbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yc6ttac-i"/><path class="kysr9_zzg"/><path class="x0ucnnbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kmeet-light" /></template>
