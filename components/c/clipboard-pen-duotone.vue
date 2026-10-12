<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc2n62g_e.css';
import '../../css/r/r7zp6bb5u.css';
import '../../css/e/emoy9fbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kc2n62g_e"/><path class="r7zp6bb5u"/><path class="emoy9fbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clipboard-pen-duotone" /></template>
