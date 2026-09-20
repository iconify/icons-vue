<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf2opmbjc.css';
import '../../css/r/r2zxf_bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qf2opmbjc"/><path class="r2zxf_bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:headset-duotone" /></template>
