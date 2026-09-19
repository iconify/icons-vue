<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za7cltxdg.css';
import '../../css/v/v_my3mlnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="za7cltxdg"/><path class="v_my3mlnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:banknoteeuro" /></template>
