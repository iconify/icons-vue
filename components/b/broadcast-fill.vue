<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc_hokbxm.css';
import '../../css/t/tknqpubcv.css';
import '../../css/l/laiohca0l.css';
import '../../css/f/fvzn7jbwv.css';
import '../../css/o/ovw8h7b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc_hokbxm"/><path class="tknqpubcv"/><path class="laiohca0l"/><path class="fvzn7jbwv"/><path class="ovw8h7b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:broadcast-fill" /></template>
