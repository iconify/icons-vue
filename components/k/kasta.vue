<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-i_qcb0v.css';
import '../../css/h/ha04bdb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-i_qcb0v"/><path clip-rule="evenodd" class="ha04bdb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kasta" /></template>
