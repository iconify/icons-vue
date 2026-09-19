<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6b0lkikv.css';
import '../../css/i/ixx3zz-eq.css';
import '../../css/m/m1ue-3z0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6b0lkikv"/><path class="ixx3zz-eq"/><path class="m1ue-3z0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-apps" /></template>
