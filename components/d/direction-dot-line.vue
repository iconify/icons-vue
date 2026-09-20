<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdagz9b_g.css';
import '../../css/m/mf2faab1e.css';
import '../../css/p/p83k8_fbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdagz9b_g"/><path class="mf2faab1e"/><path class="p83k8_fbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-dot-line" /></template>
