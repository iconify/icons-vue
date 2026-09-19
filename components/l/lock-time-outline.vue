<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbytaobxq.css';
import '../../css/h/hldc7zb1q.css';
import '../../css/p/pzaakibfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbytaobxq"/><path class="hldc7zb1q"/><path clip-rule="evenodd" class="pzaakibfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:lock-time-outline" /></template>
