<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzh7glb6r.css';
import '../../css/t/tg242fbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="zzh7glb6r"/><path class="tg242fbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:landscape" /></template>
