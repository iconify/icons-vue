<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/bffbfcbff.css';
import '../../css/z/z5y389h1p.css';
import '../../css/g/gjj6jlbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="bffbfcbff"/><path class="z5y389h1p"/><path class="gjj6jlbud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-reply-all-02" /></template>
