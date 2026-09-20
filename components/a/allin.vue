<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvzfdpbjs.css';
import '../../css/g/gicv_hb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvzfdpbjs"/><path class="gicv_hb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:allin" /></template>
