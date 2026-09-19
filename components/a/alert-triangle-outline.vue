<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rseajir1x.css';
import '../../css/i/iu35e1xme.css';
import '../../css/d/dkdq51b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rseajir1x"/><circle class="iu35e1xme"/><path class="dkdq51b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:alert-triangle-outline" /></template>
