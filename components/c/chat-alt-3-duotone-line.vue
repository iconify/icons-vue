<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd6urnymg.css';
import '../../css/d/d-18cxbdq.css';
import '../../css/g/g4amwu-cm.css';
import '../../css/x/xrumyjbiu.css';
import '../../css/k/k_n89lz_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bd6urnymg"/><path class="d-18cxbdq"/><circle class="g4amwu-cm"/><circle class="xrumyjbiu"/><circle class="k_n89lz_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-3-duotone-line" /></template>
