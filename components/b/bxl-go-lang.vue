<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuhh6ccor.css';
import '../../css/r/rk_ebkb0f.css';
import '../../css/g/g_wkhkt4o.css';
import '../../css/d/dgzseabdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuhh6ccor"/><path class="rk_ebkb0f"/><path class="g_wkhkt4o"/><path class="dgzseabdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-go-lang" /></template>
