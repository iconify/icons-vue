<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3-5_c46r.css';
import '../../css/c/clcnrxbew.css';
import '../../css/k/kihjjsb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3-5_c46r"/><path class="clcnrxbew"/><path class="kihjjsb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:koge" /></template>
