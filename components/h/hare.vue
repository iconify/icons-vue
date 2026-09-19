<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krn-s63up.css';
import '../../css/s/smbx2_k0z.css';
import '../../css/v/vto-p9r5y.css';
import '../../css/b/be-8-kdwh.css';
import '../../css/z/zs83a7b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="krn-s63up"/><path class="smbx2_k0z"/><circle class="vto-p9r5y"/><circle class="be-8-kdwh"/><path class="zs83a7b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:hare" /></template>
