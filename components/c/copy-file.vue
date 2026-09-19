<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rteynoumo.css';
import '../../css/z/zzp6lsbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rteynoumo"/><path class="zzp6lsbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:copy-file" /></template>
