<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj97bxb2b.css';
import '../../css/d/ds5jgsbxn.css';
import '../../css/z/zkybc5m-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj97bxb2b"/><circle class="ds5jgsbxn"/><path class="zkybc5m-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:kubelet-outlined" /></template>
