<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfc_4d04d.css';
import '../../css/q/q1-5e3bpd.css';
import '../../css/b/bjzdabcvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfc_4d04d"/><path class="q1-5e3bpd"/><path clip-rule="evenodd" class="bjzdabcvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:base-station-2-fill" /></template>
