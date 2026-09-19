<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q62dic9ok.css';
import '../../css/k/k-dpg_bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q62dic9ok"/><path class="k-dpg_bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-playstation-outline" /></template>
