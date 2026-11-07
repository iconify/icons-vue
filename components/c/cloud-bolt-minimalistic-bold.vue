<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srdp-xb5r.css';
import '../../css/l/lqidd2bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srdp-xb5r"/><path class="lqidd2bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-bolt-minimalistic-bold" /></template>
