<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xadmxrn2z.css';
import '../../css/t/to17vzthq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xadmxrn2z"/><path class="to17vzthq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-increase-fill-12" /></template>
